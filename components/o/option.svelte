<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ob0rwgj.css';
import '../../css/m/m7levstwq.css';
import '../../css/b/b770eaceb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q3ob0rwgj"/><path class="m7levstwq"/><path class="b770eaceb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:option" {...props}></Icon>
