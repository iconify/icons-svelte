<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7mha9bmm.css';
import '../../css/e/einl4h1qq.css';
import '../../css/a/a-5q5tb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7mha9bmm"/><path class="einl4h1qq"/><path class="a-5q5tb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:firestore" {...props}></Icon>
