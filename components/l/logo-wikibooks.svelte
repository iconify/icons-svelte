<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqbjuibkw.css';
import '../../css/c/c49engbjl.css';
import '../../css/u/u0wyggb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yqbjuibkw"/><path class="c49engbjl"/><path class="u0wyggb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-wikibooks" {...props}></Icon>
