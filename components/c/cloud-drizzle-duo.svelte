<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6kfekqvf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ob67c_b2q.css';
import '../../css/s/sb6huacei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6kfekqvf secondary"/><g class="dt0cm9dhy primary"><path class="ob67c_b2q"/><path class="sb6huacei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-drizzle-duo" {...props}></Icon>
