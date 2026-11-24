<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p9lqnjuwa.css';
import '../../css/v/v7wgf53bu.css';
import '../../css/i/iohxa7xbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="p9lqnjuwa"/><path clip-rule="evenodd" class="v7wgf53bu"/><path clip-rule="evenodd" class="iohxa7xbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-yandex-id" {...props}></Icon>
