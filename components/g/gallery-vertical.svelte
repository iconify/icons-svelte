<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssn1mkbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssn1mkbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gallery-vertical" {...props}></Icon>
