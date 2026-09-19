<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5iakzbgr.css';
import '../../css/j/jor-usn7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5iakzbgr"/><path class="jor-usn7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bolt-square" {...props}></Icon>
