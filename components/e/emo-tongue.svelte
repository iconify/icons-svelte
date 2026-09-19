<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqr1u1-go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":824,"height":1000};
const content = `<path class="pqr1u1-go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-tongue" {...props}></Icon>
