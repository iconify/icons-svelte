<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmp6hg-nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dmp6hg-nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:doc-new" {...props}></Icon>
