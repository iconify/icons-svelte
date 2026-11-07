<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj6z6-b0q.css';
import '../../css/p/plsjqqb0l.css';
import '../../css/u/ubakjmb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj6z6-b0q"/><path class="plsjqqb0l"/><path clip-rule="evenodd" class="ubakjmb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-new-outline" {...props}></Icon>
