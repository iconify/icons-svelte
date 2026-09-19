<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v36ogrb8e.css';
import '../../css/c/c4-96kq0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v36ogrb8e"/><path class="c4-96kq0k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:meat-boxed-filled" {...props}></Icon>
