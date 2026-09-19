<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb3dnfb0c.css';
import '../../css/g/gsllvxbkr.css';
import '../../css/k/k09zifbmd.css';
import '../../css/x/x7axkclvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cb3dnfb0c"/><g class="gsllvxbkr"><path class="k09zifbmd"/><path class="x7axkclvw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:bearish" {...props}></Icon>
