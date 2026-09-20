<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb_q9yb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb_q9yb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:primefaces" {...props}></Icon>
