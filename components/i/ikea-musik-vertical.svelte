<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dob6lsbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dob6lsbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-musik-vertical" {...props}></Icon>
