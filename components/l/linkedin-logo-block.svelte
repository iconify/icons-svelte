<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj923kb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mj923kb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:linkedin-logo-block" {...props}></Icon>
