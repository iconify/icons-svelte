<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a89cky7-t.css';
import '../../css/a/ajlhn96ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":208,"height":128};
const content = `<path clip-rule="evenodd" class="a89cky7-t"/><path class="ajlhn96ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:markdown-light" {...props}></Icon>
