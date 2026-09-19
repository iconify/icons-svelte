<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_86wrbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_86wrbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:readme" {...props}></Icon>
