<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo81odqdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yo81odqdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home5" {...props}></Icon>
