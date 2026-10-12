<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0_bq9h8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0_bq9h8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layout-template-filled" {...props}></Icon>
