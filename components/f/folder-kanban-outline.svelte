<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxodcsbxg.css';
import '../../css/b/bioritexk.css';
import '../../css/h/hmpjhub9l.css';
import '../../css/p/pzmtr-buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxodcsbxg"/><path class="bioritexk"/><path class="hmpjhub9l"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-kanban-outline" {...props}></Icon>
