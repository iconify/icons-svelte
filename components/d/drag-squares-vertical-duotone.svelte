<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9r6e7sfq.css';
import '../../css/c/c7rjmslqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9r6e7sfq"/><path clip-rule="evenodd" class="c7rjmslqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:drag-squares-vertical-duotone" {...props}></Icon>
