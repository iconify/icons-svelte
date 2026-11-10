<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr7qlh-st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr7qlh-st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cos" {...props}></Icon>
