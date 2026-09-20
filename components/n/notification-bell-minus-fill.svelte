<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6wahwc1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6wahwc1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-minus-fill" {...props}></Icon>
