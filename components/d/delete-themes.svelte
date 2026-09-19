<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/v/vxysmzw3k.css';
import '../../css/y/yfs_czbgj.css';
import '../../css/i/iaf4m8_yn.css';
import '../../css/u/uulr82dkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="vxysmzw3k"/><path class="yfs_czbgj"/><path class="iaf4m8_yn"/><path class="uulr82dkw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:delete-themes" {...props}></Icon>
