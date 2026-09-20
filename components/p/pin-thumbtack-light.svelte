<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw13j-wcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw13j-wcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pin-thumbtack-light" {...props}></Icon>
