<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onjqb9blp.css';
import '../../css/g/g3refjfpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onjqb9blp"/><path class="g3refjfpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-git-2-filled" {...props}></Icon>
