<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3lca2bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3lca2bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-up-right-box-sharp" {...props}></Icon>
