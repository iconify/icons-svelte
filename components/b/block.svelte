<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ellkj-bdc.css';
import '../../css/q/qhrkrwb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ellkj-bdc"/><path class="qhrkrwb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:block" {...props}></Icon>
