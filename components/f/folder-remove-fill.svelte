<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aly8xt7ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aly8xt7ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:folder-remove-fill" {...props}></Icon>
