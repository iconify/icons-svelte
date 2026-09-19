<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ona21ubhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ona21ubhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hashtag" {...props}></Icon>
