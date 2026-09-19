<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtfmx7b3v.css';
import '../../css/c/c_7supbtj.css';
import '../../css/n/ng087tlft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="wtfmx7b3v"><path class="c_7supbtj"/><path class="ng087tlft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:down" {...props}></Icon>
