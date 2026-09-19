<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye7a0cc3i.css';
import '../../css/l/leeyffb0z.css';
import '../../css/f/f6ccjno1g.css';
import '../../css/m/mvlcevogs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye7a0cc3i"/><path class="leeyffb0z"/><circle class="f6ccjno1g"/><path class="mvlcevogs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cast" {...props}></Icon>
