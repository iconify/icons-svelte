<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug7cnlp7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug7cnlp7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ada" {...props}></Icon>
