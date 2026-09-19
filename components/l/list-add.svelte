<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o64e54bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o64e54bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:list-add" {...props}></Icon>
