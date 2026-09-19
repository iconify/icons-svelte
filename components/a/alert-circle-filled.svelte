<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smqjcg2tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smqjcg2tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alert-circle-filled" {...props}></Icon>
