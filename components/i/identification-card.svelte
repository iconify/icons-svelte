<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guc1_jbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="guc1_jbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:identification-card" {...props}></Icon>
