<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nte24mkhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nte24mkhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:planet3" {...props}></Icon>
