<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu5nodbov.css';
import '../../css/w/wu_mdhb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu5nodbov"/><path class="wu_mdhb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:black-lives-matter" {...props}></Icon>
