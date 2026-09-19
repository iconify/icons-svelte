<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dncihhclw.css';
import '../../css/a/a2k6oubdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dncihhclw"/><path class="a2k6oubdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-right-stroke-circle-filled" {...props}></Icon>
