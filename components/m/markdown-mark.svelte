<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2eg_5l7t.css';
import '../../css/x/xlm34w3pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z2eg_5l7t"/><path clip-rule="evenodd" class="xlm34w3pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:markdown-mark" {...props}></Icon>
