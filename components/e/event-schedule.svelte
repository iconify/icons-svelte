<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-kkh0h8n.css';
import '../../css/k/kj5p4ecrw.css';
import '../../css/n/n_757dk6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s-kkh0h8n"/><path class="kj5p4ecrw"/><path class="n_757dk6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:event-schedule" {...props}></Icon>
