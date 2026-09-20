<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0un1obzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0un1obzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-forward-fill" {...props}></Icon>
