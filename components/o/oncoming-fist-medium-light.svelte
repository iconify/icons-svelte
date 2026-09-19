<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l1csdzbsc.css';
import '../../css/b/brktsgbib.css';
import '../../css/t/tr8rqmbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l1csdzbsc"/><path class="brktsgbib"/><path class="tr8rqmbhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:oncoming-fist-medium-light" {...props}></Icon>
