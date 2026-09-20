<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t80w8jedb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t80w8jedb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-question-fill" {...props}></Icon>
