<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za30h5bbb.css';
import '../../css/l/la7u05btg.css';
import '../../css/t/trua1bnbj.css';
import '../../css/n/no056qffi.css';
import '../../css/u/uksulubnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="za30h5bbb"/><path class="la7u05btg"/><path class="trua1bnbj"/><path class="no056qffi"/><path class="uksulubnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:control-room-48" {...props}></Icon>
