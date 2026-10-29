<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qczs5sb6a.css';
import '../../css/h/hps0sxa7g.css';
import '../../css/z/z_b_ocbhl.css';
import '../../css/u/uppje8bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qczs5sb6a"/><path class="hps0sxa7g"/><path class="z_b_ocbhl"/><path class="uppje8bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:laptop" {...props}></Icon>
