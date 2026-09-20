<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4j-itpzn.css';
import '../../css/a/azxq-6bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4j-itpzn"/><path class="azxq-6bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-times" {...props}></Icon>
