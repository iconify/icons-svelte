<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e64hjobsd.css';
import '../../css/k/knrrbxbjz.css';
import '../../css/p/pbkjaxmeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer e64hjobsd"/><path class="duoicon-secondary-layer knrrbxbjz"/><path class="duoicon-primary-layer pbkjaxmeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:lamp-2" {...props}></Icon>
