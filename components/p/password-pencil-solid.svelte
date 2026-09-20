<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l76d3obsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l76d3obsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:password-pencil-solid" {...props}></Icon>
