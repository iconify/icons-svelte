<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/k/kk2albseo.css';
import '../../css/b/bcz577s3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="kk2albseo"/><path class="bcz577s3v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:ionic-16" {...props}></Icon>
