<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3gzm8rrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n3gzm8rrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:clear" {...props}></Icon>
