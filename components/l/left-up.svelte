<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyqta459c.css';
import '../../css/i/i1nvd4bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yyqta459c"/><path class="i1nvd4bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:left-up" {...props}></Icon>
