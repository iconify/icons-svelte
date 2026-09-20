<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eizb1y4-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eizb1y4-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-angular-filled" {...props}></Icon>
