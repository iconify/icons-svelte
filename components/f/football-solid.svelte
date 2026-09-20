<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9r4e7esb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9r4e7esb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:football-solid" {...props}></Icon>
