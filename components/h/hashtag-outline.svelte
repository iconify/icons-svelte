<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvvpg1bae.css';
import '../../css/o/o2fnn15tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvvpg1bae"/><path class="o2fnn15tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:hashtag-outline" {...props}></Icon>
