<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4xxsdjfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4xxsdjfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-muted-fill" {...props}></Icon>
