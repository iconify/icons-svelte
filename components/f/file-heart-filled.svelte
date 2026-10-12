<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb4svm1zh.css';
import '../../css/s/s3-i80dqa.css';
import '../../css/k/ks00dfbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb4svm1zh"/><path class="s3-i80dqa"/><path class="ks00dfbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-heart-filled" {...props}></Icon>
