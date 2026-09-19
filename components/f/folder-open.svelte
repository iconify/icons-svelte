<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xag_4tblj.css';
import '../../css/w/wjb62bbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer xag_4tblj"/><path class="duoicon-primary-layer wjb62bbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:folder-open" {...props}></Icon>
