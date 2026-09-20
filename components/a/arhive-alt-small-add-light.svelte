<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/t/tvwa76lwl.css';
import '../../css/c/cwmzxgbha.css';
import '../../css/n/nvif07b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="tvwa76lwl"/><path class="cwmzxgbha"/><circle class="nvif07b4t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arhive-alt-small-add-light" {...props}></Icon>
