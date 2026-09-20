<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia2agsb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-7.5};
const content = `<path class="ia2agsb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:color" {...props}></Icon>
