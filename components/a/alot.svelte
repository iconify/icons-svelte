<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt8069bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt8069bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:alot" {...props}></Icon>
