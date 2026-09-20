<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s88_b-8zu.css';
import '../../css/j/jjbqhzpum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s88_b-8zu"/><path class="jjbqhzpum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-to-library-fill" {...props}></Icon>
