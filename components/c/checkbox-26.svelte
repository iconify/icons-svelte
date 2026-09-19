<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jji2zbjkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="jji2zbjkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:checkbox-26" {...props}></Icon>
