<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmuvz90jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cmuvz90jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:guarani-sign" {...props}></Icon>
