<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxh_a9ajg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxh_a9ajg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:form-filled" {...props}></Icon>
