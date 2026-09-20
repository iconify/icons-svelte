<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u441bm6ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u441bm6ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:kaggle" {...props}></Icon>
