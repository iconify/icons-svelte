<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o300w3m6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o300w3m6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:blood-bag-cross-bold" {...props}></Icon>
