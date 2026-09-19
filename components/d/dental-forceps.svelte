<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7v-nsz8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d7v-nsz8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:dental-forceps" {...props}></Icon>
