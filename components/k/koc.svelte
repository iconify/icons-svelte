<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr0-kzblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0-kzblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:koc" {...props}></Icon>
