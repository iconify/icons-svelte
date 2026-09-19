<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c18qw3bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c18qw3bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:meet-and-greet-filled" {...props}></Icon>
