<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0iha821l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0iha821l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-g" {...props}></Icon>
