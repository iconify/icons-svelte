<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic7c4od3i.css';
import '../../css/a/aciwzxbfa.css';
import '../../css/q/qya8mr1nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ic7c4od3i"/><path class="aciwzxbfa"/><path class="qya8mr1nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fireplace-20" {...props}></Icon>
