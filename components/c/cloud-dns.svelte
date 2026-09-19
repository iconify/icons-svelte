<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi_u5pbln.css';
import '../../css/i/ieryktbul.css';
import '../../css/r/rk8ixyn7u.css';
import '../../css/t/t3vv60b-u.css';
import '../../css/u/ul70_o04q.css';
import '../../css/f/f1eous41b.css';
import '../../css/w/wdvat9brn.css';
import '../../css/u/utpdeffgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi_u5pbln"/><path class="ieryktbul"/><path class="rk8ixyn7u"/><path class="t3vv60b-u"/><path class="ul70_o04q"/><path class="f1eous41b"/><path class="wdvat9brn"/><path class="utpdeffgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-dns" {...props}></Icon>
