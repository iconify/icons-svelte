<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcwb7obit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zcwb7obit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:amphora-filled" {...props}></Icon>
