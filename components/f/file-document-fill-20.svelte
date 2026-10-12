<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7oerkp_t.css';
import '../../css/j/j11y15vpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b7oerkp_t"/><path class="j11y15vpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-document-fill-20" {...props}></Icon>
