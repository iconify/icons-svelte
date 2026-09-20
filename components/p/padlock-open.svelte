<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka3v7gmwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="ka3v7gmwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:padlock-open" {...props}></Icon>
