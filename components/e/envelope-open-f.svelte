<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4zknkvgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="o4zknkvgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:envelope-open-f" {...props}></Icon>
