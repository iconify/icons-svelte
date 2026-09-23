<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i52wc5bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":33};
const content = `<path clip-rule="evenodd" class="i52wc5bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:okta" {...props}></Icon>
