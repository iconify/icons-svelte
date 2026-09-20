<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c06fh1vhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c06fh1vhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codesandbox" {...props}></Icon>
