<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hqkfeobqj.css';
import '../../css/e/e81n7dqey.css';
import '../../css/b/bo7xhxbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hqkfeobqj"/><path class="e81n7dqey"/><path clip-rule="evenodd" class="bo7xhxbdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fill-color-solid" {...props}></Icon>
