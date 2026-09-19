<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chikk6bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chikk6bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:edit-pencil-02" {...props}></Icon>
