<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo1n_uf6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vo1n_uf6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:octagon-x-solid" {...props}></Icon>
