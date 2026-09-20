<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5i1g5b_t.css';
import '../../css/c/crx0wqnqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5i1g5b_t"/><path class="crx0wqnqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mvl" {...props}></Icon>
