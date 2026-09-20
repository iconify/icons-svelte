<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tc51908st.css';
import '../../css/h/h07egnnok.css';
import '../../css/e/eld-26s5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="tc51908st"/><path class="h07egnnok"/><path clip-rule="evenodd" class="eld-26s5h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:feed" {...props}></Icon>
