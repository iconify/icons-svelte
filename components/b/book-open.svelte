<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edtsal6eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edtsal6eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:book-open" {...props}></Icon>
