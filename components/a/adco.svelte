<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyp364biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wyp364biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:adco" {...props}></Icon>
