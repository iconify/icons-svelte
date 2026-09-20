<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiy3sgb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eiy3sgb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-question" {...props}></Icon>
