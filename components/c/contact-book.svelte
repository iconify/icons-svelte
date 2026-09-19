<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv8augtve.css';
import '../../css/c/cqedrde9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv8augtve"/><path class="cqedrde9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:contact-book" {...props}></Icon>
