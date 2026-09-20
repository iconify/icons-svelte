<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns8hzw0md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns8hzw0md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:phone-silent" {...props}></Icon>
