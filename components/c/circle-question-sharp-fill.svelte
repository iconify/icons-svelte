<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rroqv4b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rroqv4b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-question-sharp-fill" {...props}></Icon>
