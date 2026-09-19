<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbsi7kbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bbsi7kbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:bmw" {...props}></Icon>
