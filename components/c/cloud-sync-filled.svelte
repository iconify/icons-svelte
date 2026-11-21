<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxomvab2t.css';
import '../../css/a/abbplybds.css';
import '../../css/e/eupxy9tmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxomvab2t"/><path class="abbplybds"/><path class="eupxy9tmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-sync-filled" {...props}></Icon>
