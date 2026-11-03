<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao0f3ab2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao0f3ab2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:edit-pencil-line-02" {...props}></Icon>
