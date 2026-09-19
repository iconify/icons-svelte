<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jor-usn7v.css';
import '../../css/h/hmlz4sbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jor-usn7v"/><path class="hmlz4sbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:form" {...props}></Icon>
