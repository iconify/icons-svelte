<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/tcbeiybdg.css';
import '../../css/c/c02hgdc7d.css';
import '../../css/a/a2wwsgbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tcbeiybdg"/><path class="c02hgdc7d"/><path class="a2wwsgbar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bug-slash" {...props}></Icon>
