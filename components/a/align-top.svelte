<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/ann80wu5h.css';
import '../../css/b/b8oyz2b-k.css';
import '../../css/f/fllxh0mbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ann80wu5h"/><rect transform="rotate(180 19.75 16.25)" class="b8oyz2b-k"/><rect transform="rotate(180 10.25 21.25)" class="fllxh0mbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:align-top" {...props}></Icon>
