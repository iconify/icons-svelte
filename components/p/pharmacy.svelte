<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1wy29y8k.css';
import '../../css/h/hhrsgwhff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1wy29y8k"/><path class="hhrsgwhff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pharmacy" {...props}></Icon>
