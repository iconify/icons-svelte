<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abjm_pc7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abjm_pc7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:api-book" {...props}></Icon>
