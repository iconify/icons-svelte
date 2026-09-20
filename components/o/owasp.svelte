<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opz9j5bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opz9j5bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:owasp" {...props}></Icon>
