<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esl4sxwch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="esl4sxwch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-divide-filled" {...props}></Icon>
