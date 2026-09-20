<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kav1tbf9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kav1tbf9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-a-z" {...props}></Icon>
