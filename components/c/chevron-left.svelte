<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk2a72bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hk2a72bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chevron-left" {...props}></Icon>
