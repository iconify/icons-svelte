<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adm_kkbuq.css';
import '../../css/m/mus2fv8bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adm_kkbuq"/><path class="mus2fv8bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:file-question" {...props}></Icon>
